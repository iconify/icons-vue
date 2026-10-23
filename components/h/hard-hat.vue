<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjrzchbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjrzchbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:hard-hat" /></template>
