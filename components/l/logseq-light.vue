<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtmtpb1fz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wtmtpb1fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:logseq-light" /></template>
