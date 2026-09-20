<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w27wi4ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w27wi4ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-positive" /></template>
