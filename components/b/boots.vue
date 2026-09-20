<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea3x4_mfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea3x4_mfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:boots" /></template>
