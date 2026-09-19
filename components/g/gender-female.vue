<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n49mtlg2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n49mtlg2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:gender-female" /></template>
