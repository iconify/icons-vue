<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4paw-bkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4paw-bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:heart-add" /></template>
