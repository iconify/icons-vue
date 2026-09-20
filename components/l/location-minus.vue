<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibqcccctl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibqcccctl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:location-minus" /></template>
