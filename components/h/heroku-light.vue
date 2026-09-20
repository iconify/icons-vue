<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epaa86_qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="epaa86_qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:heroku-light" /></template>
