<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa3ll2bzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa3ll2bzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kfc-legacy" /></template>
