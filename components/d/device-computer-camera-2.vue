<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1y4hnr9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1y4hnr9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-computer-camera-2" /></template>
