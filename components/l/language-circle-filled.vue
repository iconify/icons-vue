<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icgv--bfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icgv--bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:language-circle-filled" /></template>
