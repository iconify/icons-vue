<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4v2imb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k4v2imb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-meet-light" /></template>
