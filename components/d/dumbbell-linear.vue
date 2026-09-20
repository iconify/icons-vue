<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqosobbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqosobbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dumbbell-linear" /></template>
