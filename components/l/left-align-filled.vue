<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4-3i5bdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v4-3i5bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:left-align-filled" /></template>
