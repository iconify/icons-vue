<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuxz6hvqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="yuxz6hvqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:heart-slash-circle" /></template>
