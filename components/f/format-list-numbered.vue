<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yen6d0buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yen6d0buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-list-numbered" /></template>
