<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-i-brbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-i-brbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:image3" /></template>
