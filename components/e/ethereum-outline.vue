<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1dy8tbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f1dy8tbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:ethereum-outline" /></template>
