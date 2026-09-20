<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwm9cd21b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwm9cd21b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:charging-pile-2-fill" /></template>
