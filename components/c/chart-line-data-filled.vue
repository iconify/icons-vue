<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct6gqlwrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct6gqlwrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-line-data-filled" /></template>
