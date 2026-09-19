<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ady3sabzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ady3sabzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:jpg-download" /></template>
