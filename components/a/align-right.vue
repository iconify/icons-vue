<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kniqxnbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kniqxnbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:align-right" /></template>
