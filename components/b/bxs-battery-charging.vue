<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocfpx4bah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocfpx4bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-battery-charging" /></template>
