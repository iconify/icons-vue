<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_s23zb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a_s23zb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-beside-car" /></template>
