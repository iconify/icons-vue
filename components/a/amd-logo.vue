<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g01t5fb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g01t5fb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:amd-logo" /></template>
