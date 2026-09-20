<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdxq43g1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qdxq43g1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:barbecue-grill-with-steam" /></template>
