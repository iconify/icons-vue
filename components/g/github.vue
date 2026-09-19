<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un7e-x04j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un7e-x04j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:github" /></template>
