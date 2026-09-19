<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uph1ozkms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uph1ozkms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:letter-bb" /></template>
