<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr1e3j9gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr1e3j9gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-slash-solid" /></template>
