<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkvvucbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jkvvucbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:kick-16" /></template>
