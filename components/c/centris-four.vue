<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6lc5xboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6lc5xboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:centris-four" /></template>
