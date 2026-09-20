<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbmwvobmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="wbmwvobmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:chevron-right-small" /></template>
