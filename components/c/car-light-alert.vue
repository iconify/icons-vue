<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz8ajv6sy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz8ajv6sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-light-alert" /></template>
