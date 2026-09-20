<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su1vn_25q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su1vn_25q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:location-down" /></template>
