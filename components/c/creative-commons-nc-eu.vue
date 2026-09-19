<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtdx1lb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="gtdx1lb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:creative-commons-nc-eu" /></template>
