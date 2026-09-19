<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmqjhwbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmqjhwbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-circle-up-right-filled" /></template>
