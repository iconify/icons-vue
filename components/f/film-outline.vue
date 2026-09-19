<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1s_y2l-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1s_y2l-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:film-outline" /></template>
