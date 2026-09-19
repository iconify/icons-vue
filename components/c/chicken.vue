<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c056xx9hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c056xx9hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:chicken" /></template>
