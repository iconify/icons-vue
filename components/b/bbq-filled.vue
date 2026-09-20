<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq8bihblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cq8bihblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:bbq-filled" /></template>
