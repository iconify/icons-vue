<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtaosvumk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtaosvumk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:house-fill" /></template>
