<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3he0ryws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m3he0ryws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:coffee-cup" /></template>
