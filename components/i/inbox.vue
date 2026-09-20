<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay2ifz99p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ay2ifz99p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:inbox" /></template>
