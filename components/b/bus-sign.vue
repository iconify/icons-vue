<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikk0jabqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikk0jabqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bus-sign" /></template>
