<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjlnsfbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xjlnsfbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:arduino" /></template>
