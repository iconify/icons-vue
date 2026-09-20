<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbxbsj5py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbxbsj5py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:event-busy-outline" /></template>
