<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz7jn38ey.css';
import '../../css/y/ynkxq5xnv.css';
import '../../css/a/asevnlbpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tz7jn38ey"/><path class="ynkxq5xnv"/><path class="asevnlbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ice" /></template>
