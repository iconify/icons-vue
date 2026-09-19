<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlj98nmzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlj98nmzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:fingerprint-scan" /></template>
