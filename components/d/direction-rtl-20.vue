<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eba7bgh4x.css';
import '../../css/k/k-8fhdbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eba7bgh4x"/><path class="k-8fhdbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:direction-rtl-20" /></template>
