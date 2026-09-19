<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bitiamboi.css';
import '../../css/z/zbnf4mu7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bitiamboi"/><path class="zbnf4mu7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-aws" /></template>
