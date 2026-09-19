<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbu-lrbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbu-lrbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrow-bottom-left" /></template>
