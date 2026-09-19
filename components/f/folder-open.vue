<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7i-_hv-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p7i-_hv-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:folder-open" /></template>
