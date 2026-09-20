<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me81uw3xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="me81uw3xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:crossed-bones" /></template>
