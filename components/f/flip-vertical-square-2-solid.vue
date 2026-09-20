<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm1x6fvcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vm1x6fvcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:flip-vertical-square-2-solid" /></template>
