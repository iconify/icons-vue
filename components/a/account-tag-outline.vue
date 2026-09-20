<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shfib-biy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shfib-biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-tag-outline" /></template>
