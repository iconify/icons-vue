<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhr7jzdyv.css';
import '../../css/y/yj4ra116h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xhr7jzdyv"/><path class="yj4ra116h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:istanbul" /></template>
