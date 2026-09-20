<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4yyh0biz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4yyh0biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:arv" /></template>
