<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu1l5dbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu1l5dbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gesture-unlock-line" /></template>
