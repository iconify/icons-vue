<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izyf8vb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izyf8vb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:left-two-headed-fill" /></template>
