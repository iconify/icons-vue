<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe9-4qb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xe9-4qb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:link-chain-flat" /></template>
