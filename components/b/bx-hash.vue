<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw780st6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw780st6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-hash" /></template>
