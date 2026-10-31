<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mub4lvbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mub4lvbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cookie" /></template>
