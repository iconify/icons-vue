<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmxqtvb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmxqtvb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:camera-2-filled" /></template>
