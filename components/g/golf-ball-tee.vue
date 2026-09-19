<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urzpa-bxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="urzpa-bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:golf-ball-tee" /></template>
