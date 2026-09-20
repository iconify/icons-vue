<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km5mez-1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km5mez-1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bing-logo-2-solid" /></template>
