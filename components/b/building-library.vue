<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk25et9co.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nk25et9co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:building-library" /></template>
