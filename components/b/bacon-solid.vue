<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h112d1ovp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h112d1ovp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bacon-solid" /></template>
