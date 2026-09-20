<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1zttk_jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g1zttk_jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:cake" /></template>
