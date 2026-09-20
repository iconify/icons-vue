<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uumv_0bli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uumv_0bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-charging-30" /></template>
