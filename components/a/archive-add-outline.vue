<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0b1rlbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0b1rlbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:archive-add-outline" /></template>
