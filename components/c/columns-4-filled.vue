<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjrotzbpr.css';
import '../../css/w/wgckvftty.css';
import '../../css/w/wh72mu7bx.css';
import '../../css/d/db6ijebmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="vjrotzbpr"/><rect class="wgckvftty"/><rect class="wh72mu7bx"/><rect class="db6ijebmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:columns-4-filled" /></template>
