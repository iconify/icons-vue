<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5z957buc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path clip-rule="evenodd" class="o5z957buc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:caret-down" /></template>
