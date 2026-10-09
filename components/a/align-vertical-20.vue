<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uquk1jb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uquk1jb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-vertical-20" /></template>
