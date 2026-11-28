<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmeug5b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmeug5b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:alarm-clock-x-solid" /></template>
