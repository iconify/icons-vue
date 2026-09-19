<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0epiibab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="g0epiibab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:colon-sign" /></template>
