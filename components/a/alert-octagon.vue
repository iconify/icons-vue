<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y04j6gm0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y04j6gm0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:alert-octagon" /></template>
