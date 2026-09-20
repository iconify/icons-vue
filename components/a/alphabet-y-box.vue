<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms_36u3ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms_36u3ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-y-box" /></template>
