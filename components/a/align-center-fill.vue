<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfl3-yyya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfl3-yyya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-center-fill" /></template>
