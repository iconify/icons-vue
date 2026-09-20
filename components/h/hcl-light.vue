<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw9st_b5f.css';
import '../../css/f/f7jhyeftq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pw9st_b5f"/><path class="f7jhyeftq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:hcl-light" /></template>
