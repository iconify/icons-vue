<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygj9995gz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygj9995gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:award-trophy-1" /></template>
