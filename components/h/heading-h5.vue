<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzvoi370p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzvoi370p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:heading-h5" /></template>
