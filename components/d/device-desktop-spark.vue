<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkg5xlu5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkg5xlu5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-desktop-spark" /></template>
