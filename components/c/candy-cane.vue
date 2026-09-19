<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpyf24fdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpyf24fdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:candy-cane" /></template>
