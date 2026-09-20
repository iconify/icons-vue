<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xboe5vb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xboe5vb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:heart-fill-24" /></template>
