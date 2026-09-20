<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttzz6hdgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttzz6hdgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ironing" /></template>
