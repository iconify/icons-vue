<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzedyzb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kzedyzb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:file" /></template>
