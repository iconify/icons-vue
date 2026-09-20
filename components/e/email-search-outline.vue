<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_is6obug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_is6obug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:email-search-outline" /></template>
