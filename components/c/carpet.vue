<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gepdwrb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gepdwrb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:carpet" /></template>
