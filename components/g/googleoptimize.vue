<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9b-bxb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9b-bxb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:googleoptimize" /></template>
