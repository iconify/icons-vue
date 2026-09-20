<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7v9eabbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7v9eabbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:barley" /></template>
