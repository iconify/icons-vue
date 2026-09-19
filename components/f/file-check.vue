<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_j3_zqkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_j3_zqkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:file-check" /></template>
