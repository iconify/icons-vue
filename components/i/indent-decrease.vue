<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4_gojb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v4_gojb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:indent-decrease" /></template>
