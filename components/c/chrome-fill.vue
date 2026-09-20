<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjy1m-bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjy1m-bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chrome-fill" /></template>
