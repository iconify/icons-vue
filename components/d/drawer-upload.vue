<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czlkr0bvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czlkr0bvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:drawer-upload" /></template>
