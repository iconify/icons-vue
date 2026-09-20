<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utdu4ccld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="utdu4ccld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:download-square-bold" /></template>
