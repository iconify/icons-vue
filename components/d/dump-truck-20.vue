<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whrwdskwh.css';
import '../../css/a/ao3d_1b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="whrwdskwh"/><path class="ao3d_1b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dump-truck-20" /></template>
