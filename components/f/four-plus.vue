<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyhm07bjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zyhm07bjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:four-plus" /></template>
