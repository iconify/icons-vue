<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhp-87ykt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhp-87ykt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cards" /></template>
