<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiqrs_neo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iiqrs_neo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-imac-dollar" /></template>
