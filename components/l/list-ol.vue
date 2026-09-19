<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw-acp7gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nw-acp7gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:list-ol" /></template>
