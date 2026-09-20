<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk_2ytb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk_2ytb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:call-to-action" /></template>
