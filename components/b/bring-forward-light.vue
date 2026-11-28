<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v29kbzb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v29kbzb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bring-forward-light" /></template>
