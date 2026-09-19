<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr4ffz20i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="kr4ffz20i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:chat" /></template>
