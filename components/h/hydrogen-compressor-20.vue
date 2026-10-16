<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai3gqkb8w.css';
import '../../css/a/aga2wzbcv.css';
import '../../css/b/bgmlxcclc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ai3gqkb8w"/><path class="aga2wzbcv"/><path class="bgmlxcclc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-compressor-20" /></template>
