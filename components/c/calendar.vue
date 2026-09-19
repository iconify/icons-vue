<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm9_03bcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm9_03bcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:calendar" /></template>
