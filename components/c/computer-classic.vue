<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs66gybrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs66gybrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:computer-classic" /></template>
