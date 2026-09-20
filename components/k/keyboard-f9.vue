<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srtehsk8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srtehsk8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keyboard-f9" /></template>
