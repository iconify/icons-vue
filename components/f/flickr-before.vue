<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfoyxdpod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="sfoyxdpod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flickr-before" /></template>
