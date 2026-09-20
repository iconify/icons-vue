<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtig31boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtig31boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:btc" /></template>
