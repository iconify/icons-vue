<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqi0jcbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqi0jcbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:heart-filled" /></template>
