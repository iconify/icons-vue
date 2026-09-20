<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehkl27azb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehkl27azb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-check" /></template>
