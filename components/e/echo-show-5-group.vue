<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6v85no4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6v85no4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:echo-show-5-group" /></template>
