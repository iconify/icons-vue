<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2514jb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2514jb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fit-to-page" /></template>
