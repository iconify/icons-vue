<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2f-umren.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g2f-umren"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:database" /></template>
