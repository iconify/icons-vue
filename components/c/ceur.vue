<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkfoh8bwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkfoh8bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ceur" /></template>
