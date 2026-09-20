<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke5xj4b2r.css';
import '../../css/u/u4w6z7bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke5xj4b2r"/><path class="u4w6z7bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ccv2" /></template>
