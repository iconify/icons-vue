<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s04r6fc4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s04r6fc4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:goggles-fill" /></template>
