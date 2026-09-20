<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n07rvdbgg.css';
import '../../css/i/iigxsq-iw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n07rvdbgg"/><path class="iigxsq-iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:go" /></template>
