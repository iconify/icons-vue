<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_oqib-hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_oqib-hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-down-stroke-circle-filled" /></template>
