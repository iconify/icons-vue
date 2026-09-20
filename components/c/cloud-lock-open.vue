<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f063dbdeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f063dbdeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-lock-open" /></template>
