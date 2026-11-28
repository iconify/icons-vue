<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agdi52bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="agdi52bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:clock-plus-fill" /></template>
