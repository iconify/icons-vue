<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl7-ffbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl7-ffbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-settings" /></template>
