<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2r9ojmrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2r9ojmrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:fast-forward-solid" /></template>
