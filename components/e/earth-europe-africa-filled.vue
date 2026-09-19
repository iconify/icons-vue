<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od4db_i1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="od4db_i1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:earth-europe-africa-filled" /></template>
