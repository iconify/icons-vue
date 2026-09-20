<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/celdv5lhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="celdv5lhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:case-small-caps-16" /></template>
