<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw0qoybyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw0qoybyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:homey" /></template>
