<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hypaunbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hypaunbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:gamepad-modern" /></template>
