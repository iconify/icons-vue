<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqkmd_7zr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqkmd_7zr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:link-broken2" /></template>
