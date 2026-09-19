<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s03_u5bza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s03_u5bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-wechat" /></template>
