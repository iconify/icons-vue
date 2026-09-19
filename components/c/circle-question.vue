<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6b_jehus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i6b_jehus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-question" /></template>
