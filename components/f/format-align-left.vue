<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szfbq0a_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szfbq0a_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-align-left" /></template>
