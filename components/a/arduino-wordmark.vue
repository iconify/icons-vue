<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v78z00blh.css';
import '../../css/a/aj0gbdb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="v78z00blh"/><path class="aj0gbdb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:arduino-wordmark" /></template>
