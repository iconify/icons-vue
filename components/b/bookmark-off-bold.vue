<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcsgx-puk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcsgx-puk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-off-bold" /></template>
