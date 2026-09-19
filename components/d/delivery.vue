<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr--b0bjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xr--b0bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:delivery" /></template>
