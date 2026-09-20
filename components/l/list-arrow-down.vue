<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-cyun8kk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a-cyun8kk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:list-arrow-down" /></template>
