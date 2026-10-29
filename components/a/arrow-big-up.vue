<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnakygbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnakygbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-big-up" /></template>
