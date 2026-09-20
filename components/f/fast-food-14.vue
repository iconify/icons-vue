<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyqqu5bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="tyqqu5bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:fast-food-14" /></template>
