<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocj-alamt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocj-alamt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-vertical-distribute-center" /></template>
