<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogjhj0zyh.css';
import '../../css/s/s8-x_jb_g.css';
import '../../css/n/n198smeot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ogjhj0zyh"/><path class="s8-x_jb_g"/><path class="n198smeot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:electrical-threshold" /></template>
