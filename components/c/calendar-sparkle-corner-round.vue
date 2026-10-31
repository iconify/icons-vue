<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmkgw6vvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmkgw6vvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-sparkle-corner-round" /></template>
