<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbamhbcln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbamhbcln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-l-circle-outline" /></template>
