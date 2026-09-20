<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvy456baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvy456baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alarm-note-off" /></template>
