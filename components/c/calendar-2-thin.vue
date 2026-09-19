<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaws_22cn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kaws_22cn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:calendar-2-thin" /></template>
