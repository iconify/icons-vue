<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4oxo7lej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4oxo7lej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ip-network-outline" /></template>
