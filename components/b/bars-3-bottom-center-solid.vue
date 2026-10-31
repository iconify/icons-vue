<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9iekghug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f9iekghug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:bars-3-bottom-center-solid" /></template>
