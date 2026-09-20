<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxkhyubtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pxkhyubtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:amount-down-two-filled" /></template>
