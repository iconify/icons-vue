<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7f39lbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7f39lbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bag-tick-filled" /></template>
