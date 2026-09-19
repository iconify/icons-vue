<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z45ujbcbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z45ujbcbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:diagram-next" /></template>
