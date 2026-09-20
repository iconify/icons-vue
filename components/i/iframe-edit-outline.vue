<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9lap0bcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9lap0bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:iframe-edit-outline" /></template>
