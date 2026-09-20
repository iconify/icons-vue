<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggzbzm6kg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ggzbzm6kg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:home-smile-filled" /></template>
