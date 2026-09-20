<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxc4urb0d.css';
import '../../css/g/gks8du_si.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxc4urb0d"/><path class="gks8du_si"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:check-box" /></template>
