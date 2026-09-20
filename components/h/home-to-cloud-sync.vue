<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk6-szb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fk6-szb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:home-to-cloud-sync" /></template>
