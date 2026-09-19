<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hup4jharq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hup4jharq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-expand-02" /></template>
