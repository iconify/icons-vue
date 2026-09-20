<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifftp-7_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifftp-7_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:code-of-conduct-24" /></template>
