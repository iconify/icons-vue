<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt410iuji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt410iuji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:hourglass" /></template>
