<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt_mcy6nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt_mcy6nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:google-summer-of-code" /></template>
