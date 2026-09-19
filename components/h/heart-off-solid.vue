<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp_l5hn1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jp_l5hn1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:heart-off-solid" /></template>
