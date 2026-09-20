<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqu1uhb_e.css';
import '../../css/b/b0zme1q_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqu1uhb_e"/><path class="b0zme1q_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:controls-camera-off" /></template>
