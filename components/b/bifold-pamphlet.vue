<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbaozxt1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rbaozxt1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bifold-pamphlet" /></template>
