<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btdsy2bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="btdsy2bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ahimsa-hand" /></template>
