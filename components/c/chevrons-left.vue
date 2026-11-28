<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyxi7h06a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyxi7h06a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:chevrons-left" /></template>
