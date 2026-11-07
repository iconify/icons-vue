<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olusrszwm.css';
import '../../css/p/p5cc5fbot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olusrszwm"/><path class="p5cc5fbot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:logout-2-outline" /></template>
