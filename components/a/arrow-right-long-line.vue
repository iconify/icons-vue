<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz0yvmeas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tz0yvmeas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-right-long-line" /></template>
