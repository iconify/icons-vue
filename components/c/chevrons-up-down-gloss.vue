<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfxm7fujt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfxm7fujt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevrons-up-down-gloss" /></template>
