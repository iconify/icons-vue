<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lclx3le1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lclx3le1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:aws" /></template>
