<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuipv5w1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuipv5w1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:library" /></template>
