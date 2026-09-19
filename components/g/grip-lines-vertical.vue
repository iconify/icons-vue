<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icsu46bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":192,"height":512};
const content = `<path class="icsu46bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:grip-lines-vertical" /></template>
