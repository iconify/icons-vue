<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt6kw6_7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tt6kw6_7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:mail-o" /></template>
