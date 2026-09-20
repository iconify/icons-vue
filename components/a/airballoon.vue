<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh-r6ubyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh-r6ubyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:airballoon" /></template>
