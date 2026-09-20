<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w308l4u6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w308l4u6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-up-right" /></template>
