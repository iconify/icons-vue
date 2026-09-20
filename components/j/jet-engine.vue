<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/totd4jbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="totd4jbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:jet-engine" /></template>
