<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x58xkwtsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x58xkwtsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:briefcase-eye-outline" /></template>
