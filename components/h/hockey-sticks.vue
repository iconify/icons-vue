<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc8fqpbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc8fqpbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hockey-sticks" /></template>
