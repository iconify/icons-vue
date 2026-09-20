<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spj178bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spj178bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:google-gemini" /></template>
