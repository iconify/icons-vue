<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk4migb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk4migb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:align-horizontal-justify-end" /></template>
