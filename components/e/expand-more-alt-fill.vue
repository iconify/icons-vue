<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwyk2y6_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uwyk2y6_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:expand-more-alt-fill" /></template>
