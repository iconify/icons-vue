<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq6hl0axq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq6hl0axq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:hourglass-bottom" /></template>
