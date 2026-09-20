<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5lkugitz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5lkugitz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-charging-60" /></template>
