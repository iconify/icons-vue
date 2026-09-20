<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwmhcdcyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwmhcdcyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-connected" /></template>
