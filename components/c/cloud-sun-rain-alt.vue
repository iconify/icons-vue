<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-0q-6bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-0q-6bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-sun-rain-alt" /></template>
