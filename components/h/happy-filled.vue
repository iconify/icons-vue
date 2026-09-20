<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv0v1xbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv0v1xbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:happy-filled" /></template>
