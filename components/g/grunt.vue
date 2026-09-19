<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua7cgebor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="ua7cgebor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:grunt" /></template>
