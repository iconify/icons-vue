<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yes38jbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="check-outline"><path class="Vector yes38jbxi" clip-rule="evenodd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:check-outline" /></template>
