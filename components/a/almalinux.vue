<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azj6c3b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azj6c3b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:almalinux" /></template>
