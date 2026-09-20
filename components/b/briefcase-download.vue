<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kshhu5b0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kshhu5b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:briefcase-download" /></template>
