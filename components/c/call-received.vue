<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlu5le0mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlu5le0mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:call-received" /></template>
