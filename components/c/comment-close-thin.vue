<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1_1fhplu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1_1fhplu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:comment-close-thin" /></template>
