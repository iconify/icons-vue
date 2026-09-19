<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r85hdt1lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="r85hdt1lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:apple-alt" /></template>
