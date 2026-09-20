<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4_6otcrb.css';
import '../../css/s/sy_8ez57r.css';
import '../../css/w/wji-c-ehd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4_6otcrb"/><path class="sy_8ez57r"/><path class="wji-c-ehd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ctc" /></template>
