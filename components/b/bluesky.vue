<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwbdgq.css';
import '../../css/s/so-from-76.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwbdgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:bluesky" /></template>
