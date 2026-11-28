<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7gknnbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7gknnbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cloud-check" /></template>
