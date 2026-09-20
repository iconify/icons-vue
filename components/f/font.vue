<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysgaynbri.css';
import '../../css/w/wb-9ypfti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ysgaynbri"/><path class="wb-9ypfti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:font" /></template>
