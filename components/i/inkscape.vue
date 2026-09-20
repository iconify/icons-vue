<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-oxpzahn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-oxpzahn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:inkscape" /></template>
