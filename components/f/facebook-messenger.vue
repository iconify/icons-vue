<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5zp_6bpu.css';
import '../../css/y/ynlpaobkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5zp_6bpu"/><path class="ynlpaobkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:facebook-messenger" /></template>
