<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmksxpbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bmksxpbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crusher-20" /></template>
