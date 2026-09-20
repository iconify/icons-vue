<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtg44vu4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vtg44vu4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hourglass-outline" /></template>
