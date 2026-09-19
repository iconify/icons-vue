<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p72k2ybym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p72k2ybym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-circle-up" /></template>
