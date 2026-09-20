<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp5m3lbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wp5m3lbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:heart-rate-clipboard-remix" /></template>
