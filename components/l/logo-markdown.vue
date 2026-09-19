<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nze9ryb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nze9ryb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:logo-markdown" /></template>
