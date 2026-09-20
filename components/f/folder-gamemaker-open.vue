<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdm7i77zj.css';
import '../../css/p/p0z48hbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pdm7i77zj"/><path class="p0z48hbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-gamemaker-open" /></template>
