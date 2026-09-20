<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8zdubc5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8zdubc5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:google-plus-box" /></template>
