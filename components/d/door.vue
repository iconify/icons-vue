<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d57uaiwla.css';
import '../../css/w/wtnptnb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d57uaiwla"/><path class="wtnptnb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:door" /></template>
