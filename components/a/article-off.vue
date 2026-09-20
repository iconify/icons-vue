<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2i14cbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2i14cbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:article-off" /></template>
