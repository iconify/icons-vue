<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md75adbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="md75adbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:card-diamond" /></template>
