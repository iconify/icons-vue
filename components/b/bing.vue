<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2i50-arv.css';
import '../../css/a/adhi_y29i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2i50-arv"/><path class="adhi_y29i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:bing" /></template>
