<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl0mm4bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bl0mm4bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fire" /></template>
