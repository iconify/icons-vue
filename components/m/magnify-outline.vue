<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epl4z1bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epl4z1bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:magnify-outline" /></template>
