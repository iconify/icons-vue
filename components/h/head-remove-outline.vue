<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n07h6uase.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n07h6uase"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:head-remove-outline" /></template>
