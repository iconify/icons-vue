<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffmxou07g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffmxou07g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:heart-24px" /></template>
