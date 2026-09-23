<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1d-wu-4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1d-wu-4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:corner-right-up-fill" /></template>
