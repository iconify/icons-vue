<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw46at8gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw46at8gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:colon-solid" /></template>
