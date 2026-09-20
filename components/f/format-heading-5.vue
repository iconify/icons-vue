<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0y9095ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0y9095ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-heading-5" /></template>
