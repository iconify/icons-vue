<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suwu-_bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suwu-_bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:departure" /></template>
