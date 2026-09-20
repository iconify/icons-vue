<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1tx1rb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g1tx1rb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:four-minus" /></template>
