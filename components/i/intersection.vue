<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hammunblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":14};
const content = `<path class="hammunblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:intersection" /></template>
