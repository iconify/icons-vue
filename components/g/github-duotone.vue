<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuozmdbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary tuozmdbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:github-duotone" /></template>
