<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1y5f3xqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1y5f3xqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:backward-step" /></template>
