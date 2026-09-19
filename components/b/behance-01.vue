<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck_ndwbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck_ndwbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:behance-01" /></template>
