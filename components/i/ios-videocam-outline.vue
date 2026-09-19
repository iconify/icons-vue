<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjuulwb_p.css';
import '../../css/i/i60oecb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bjuulwb_p"/><path class="i60oecb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-videocam-outline" /></template>
