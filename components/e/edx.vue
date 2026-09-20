<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntd2lyfxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntd2lyfxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:edx" /></template>
