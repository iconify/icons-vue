<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usurg9b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usurg9b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:chevron-down-solid" /></template>
