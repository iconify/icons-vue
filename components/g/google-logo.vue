<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk57q1buv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk57q1buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-logo" /></template>
