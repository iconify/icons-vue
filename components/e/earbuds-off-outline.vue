<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9xn-jbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9xn-jbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:earbuds-off-outline" /></template>
