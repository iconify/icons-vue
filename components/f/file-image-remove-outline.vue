<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf1aab8sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf1aab8sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-image-remove-outline" /></template>
