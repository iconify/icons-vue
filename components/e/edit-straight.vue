<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjhaaozbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjhaaozbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:edit-straight" /></template>
