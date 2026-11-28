<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2dzzyjot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2dzzyjot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mail-arrow-up-solid" /></template>
