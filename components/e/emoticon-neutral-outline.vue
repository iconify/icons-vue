<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azfvvij0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azfvvij0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoticon-neutral-outline" /></template>
