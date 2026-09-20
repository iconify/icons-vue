<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iudf_ab8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iudf_ab8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:border-outside" /></template>
