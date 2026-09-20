<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmxu07dat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tmxu07dat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:adit-profile" /></template>
