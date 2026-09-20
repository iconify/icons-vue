<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/toaadoxot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="toaadoxot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bookmark-remove-outline" /></template>
