<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7kj12bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="b7kj12bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:border-top-light" /></template>
