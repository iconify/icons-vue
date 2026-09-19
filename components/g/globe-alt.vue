<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9hb5yb2a.css';
import '../../css/g/gctaj9b_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9hb5yb2a"/><path class="gctaj9b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:globe-alt" /></template>
