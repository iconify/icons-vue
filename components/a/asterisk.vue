<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfo7nws-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":348,"height":719};
const content = `<path class="dfo7nws-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:asterisk" /></template>
