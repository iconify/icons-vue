<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9w3e2bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9w3e2bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gamepad-buttons" /></template>
