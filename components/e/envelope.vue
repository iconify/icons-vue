<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqdv3t5-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqdv3t5-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:envelope" /></template>
