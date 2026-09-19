<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko--2qbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ko--2qbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:magnet" /></template>
