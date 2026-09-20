<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6zvrsm-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6zvrsm-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:goldman-sachs" /></template>
