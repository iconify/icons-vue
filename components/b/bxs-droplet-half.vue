<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikb0k8gli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikb0k8gli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-droplet-half" /></template>
