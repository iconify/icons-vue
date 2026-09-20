<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t93wronmj.css';
import '../../css/q/qi5qy6i4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="t93wronmj"/><path class="qi5qy6i4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:gridsome" /></template>
