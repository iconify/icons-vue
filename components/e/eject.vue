<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndgahnmhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndgahnmhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:eject" /></template>
