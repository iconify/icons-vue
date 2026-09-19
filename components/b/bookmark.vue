<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b72-nxbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="b72-nxbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:bookmark" /></template>
