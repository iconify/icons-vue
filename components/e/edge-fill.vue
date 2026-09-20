<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcv0d51xo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcv0d51xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:edge-fill" /></template>
