<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4smpac2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4smpac2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dice-5-line" /></template>
