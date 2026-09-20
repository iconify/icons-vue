<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy3525bwm.css';
import '../../css/d/d7q3yfbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy3525bwm"/><path class="d7q3yfbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:call-1-filled" /></template>
