<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1xb_obhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":431,"height":953};
const content = `<path class="l1xb_obhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:dollar" /></template>
