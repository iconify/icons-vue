<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cniwqxb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cniwqxb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:drink-bottle-and-drink-cup-with-straw" /></template>
