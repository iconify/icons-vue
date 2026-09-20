<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2qoqjbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2qoqjbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:border-all" /></template>
