<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poyy-gyea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="poyy-gyea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-alert" /></template>
