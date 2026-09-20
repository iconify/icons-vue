<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9oxn1w7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9oxn1w7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chart3-filled" /></template>
