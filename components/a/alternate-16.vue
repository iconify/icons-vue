<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk5xl6f6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hk5xl6f6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:alternate-16" /></template>
