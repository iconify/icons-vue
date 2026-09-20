<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khb128k1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="khb128k1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:backpack" /></template>
