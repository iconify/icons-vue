<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n860kys_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n860kys_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-down" /></template>
