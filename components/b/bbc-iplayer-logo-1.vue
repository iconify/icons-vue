<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaov8kxvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kaov8kxvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bbc-iplayer-logo-1" /></template>
