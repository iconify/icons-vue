<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6ijqvbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6ijqvbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:location-check-outline" /></template>
