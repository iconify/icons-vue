<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxl9-nbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxl9-nbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:explosion-solid" /></template>
