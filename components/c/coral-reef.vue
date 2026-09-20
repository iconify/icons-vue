<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-t8_bbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c-t8_bbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:coral-reef" /></template>
