<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rew-o_dyy.css';
import '../../css/u/ubz5-631s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rew-o_dyy"/><path class="ubz5-631s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:coldfusion" /></template>
