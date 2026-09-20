<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0v2wcciq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b0v2wcciq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:kai-os-logo-block" /></template>
