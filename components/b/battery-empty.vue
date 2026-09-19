<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wipyugbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wipyugbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:battery-empty" /></template>
