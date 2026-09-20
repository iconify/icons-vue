<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/betyx0-oa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="betyx0-oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:douban-read" /></template>
