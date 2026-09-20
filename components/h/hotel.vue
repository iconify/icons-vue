<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi8q3-b_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hi8q3-b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hotel" /></template>
