<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waci2fbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="waci2fbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ear-hearing-solid" /></template>
