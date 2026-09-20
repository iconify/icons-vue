<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuru8lc6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xuru8lc6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:magnet-filled" /></template>
