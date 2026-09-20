<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lks628r3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lks628r3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-compress-all" /></template>
