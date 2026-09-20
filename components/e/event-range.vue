<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yif2k3mfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yif2k3mfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:event-range" /></template>
