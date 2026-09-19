<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuoa-cbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuoa-cbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bookmark" /></template>
