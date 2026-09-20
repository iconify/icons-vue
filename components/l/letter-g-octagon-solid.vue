<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_5baebsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_5baebsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-g-octagon-solid" /></template>
