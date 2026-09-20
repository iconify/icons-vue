<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mds8r6baq.css';
import '../../css/d/d18mv78yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mds8r6baq"/><path class="d18mv78yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:imdb" /></template>
