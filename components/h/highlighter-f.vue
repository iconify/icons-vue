<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2lcz1btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1,"top":-1.5};
const content = `<path class="q2lcz1btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:highlighter-f" /></template>
