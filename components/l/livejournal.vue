<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkzm34b8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkzm34b8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:livejournal" /></template>
