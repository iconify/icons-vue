<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzcdafbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzcdafbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alarm-note" /></template>
