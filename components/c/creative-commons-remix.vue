<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_2evxb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="c_2evxb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:creative-commons-remix" /></template>
