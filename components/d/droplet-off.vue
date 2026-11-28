<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joyy5sbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="joyy5sbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:droplet-off" /></template>
