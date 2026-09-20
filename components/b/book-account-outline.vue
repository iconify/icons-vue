<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyudxrb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyudxrb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-account-outline" /></template>
