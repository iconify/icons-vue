<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx-ibsb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx-ibsb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:a-arrow-down" /></template>
