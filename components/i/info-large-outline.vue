<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cium_fbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cium_fbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:info-large-outline" /></template>
