<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji14mos9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ji14mos9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:heart-off" /></template>
