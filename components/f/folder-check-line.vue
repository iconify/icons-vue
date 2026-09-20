<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad2r3cjik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad2r3cjik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:folder-check-line" /></template>
