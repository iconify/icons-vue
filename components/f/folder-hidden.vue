<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs_mi8b4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs_mi8b4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-hidden" /></template>
