<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib_sq-b0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib_sq-b0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:align-center-justify" /></template>
