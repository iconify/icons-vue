<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhi51fbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhi51fbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:confetti-filled" /></template>
