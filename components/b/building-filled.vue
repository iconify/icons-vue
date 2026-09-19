<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv3lywbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zv3lywbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:building-filled" /></template>
