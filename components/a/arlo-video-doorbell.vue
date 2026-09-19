<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm_dlq0xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm_dlq0xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:arlo-video-doorbell" /></template>
