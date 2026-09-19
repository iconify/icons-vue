<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1p_8cbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1p_8cbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:clipboard-cancel-filled" /></template>
