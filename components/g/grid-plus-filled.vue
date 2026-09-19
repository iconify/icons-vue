<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u20c2ybqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u20c2ybqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:grid-plus-filled" /></template>
