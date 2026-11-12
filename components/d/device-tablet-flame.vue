<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0l7-ebsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0l7-ebsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-tablet-flame" /></template>
