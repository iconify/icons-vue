<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa4j5f3rn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xa4j5f3rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ladder" /></template>
