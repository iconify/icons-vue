<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g64400p-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g64400p-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:groovy" /></template>
