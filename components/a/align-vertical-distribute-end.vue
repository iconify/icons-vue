<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y170jge6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y170jge6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-vertical-distribute-end" /></template>
