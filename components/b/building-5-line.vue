<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4-av5bbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4-av5bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:building-5-line" /></template>
