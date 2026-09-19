<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io_dcmbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io_dcmbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:alphabet-arabic" /></template>
