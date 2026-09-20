<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drsxbb9iy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drsxbb9iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-l-filled" /></template>
