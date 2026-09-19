<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj9y470xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hj9y470xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:cloud-clock-fill" /></template>
