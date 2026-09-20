<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_4panb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a_4panb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:level-none-rtl" /></template>
