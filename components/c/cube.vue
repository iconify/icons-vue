<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kald952wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="kald952wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:cube" /></template>
