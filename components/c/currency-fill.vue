<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn8g8r50i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn8g8r50i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:currency-fill" /></template>
