<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyv5sjoyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyv5sjoyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:device-camera-24" /></template>
