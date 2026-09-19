<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfk4x64-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nfk4x64-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:clock-arrow-rotate-left" /></template>
