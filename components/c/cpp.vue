<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_t1md8jp.css';
import '../../css/i/ihw0bkbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i_t1md8jp"/><path class="ihw0bkbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:cpp" /></template>
