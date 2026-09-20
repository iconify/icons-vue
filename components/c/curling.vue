<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udp4kkb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udp4kkb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:curling" /></template>
