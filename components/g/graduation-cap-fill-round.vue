<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nensndbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nensndbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:graduation-cap-fill-round" /></template>
