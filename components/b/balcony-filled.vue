<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwx32-blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwx32-blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:balcony-filled" /></template>
