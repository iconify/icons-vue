<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrjpsbcaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrjpsbcaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fireplace-off" /></template>
