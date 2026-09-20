<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp7whfbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dp7whfbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bake" /></template>
