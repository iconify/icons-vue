<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rezryb9cd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rezryb9cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-horizontal-share" /></template>
