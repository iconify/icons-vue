<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqy47e33q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqy47e33q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clipboard-data-filled" /></template>
