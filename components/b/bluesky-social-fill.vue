<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alhq8vbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alhq8vbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bluesky-social-fill" /></template>
