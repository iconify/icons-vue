<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkp47mbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkp47mbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comment-quick" /></template>
