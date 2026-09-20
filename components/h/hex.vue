<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shu57bcsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="shu57bcsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:hex" /></template>
