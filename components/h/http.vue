<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyw18zbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gyw18zbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:http" /></template>
