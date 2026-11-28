<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfbo3h2tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfbo3h2tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:fingerprint-x" /></template>
