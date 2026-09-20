<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1nuh0b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1nuh0b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-back" /></template>
