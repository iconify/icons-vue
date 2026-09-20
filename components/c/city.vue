<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts5-r4bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts5-r4bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:city" /></template>
