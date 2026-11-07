<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/encu70b2r.css';
import '../../css/g/gp0qeb1le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="encu70b2r"/><path class="gp0qeb1le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:call-chat-bold" /></template>
