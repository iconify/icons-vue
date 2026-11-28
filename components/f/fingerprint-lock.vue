<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnid7pbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnid7pbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:fingerprint-lock" /></template>
