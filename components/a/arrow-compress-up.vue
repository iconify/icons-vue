<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcuck66nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcuck66nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-compress-up" /></template>
