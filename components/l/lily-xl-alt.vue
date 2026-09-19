<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ion_h5bia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ion_h5bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lily-xl-alt" /></template>
