<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo2s3nbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo2s3nbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-horizontal-off" /></template>
