<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0erngb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0erngb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:equipment-gym-01" /></template>
