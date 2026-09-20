<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-9axiq1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-9axiq1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-lock" /></template>
