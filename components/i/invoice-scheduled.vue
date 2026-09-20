<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-z2yuw-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-z2yuw-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-scheduled" /></template>
