<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eragz99eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="eragz99eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:commenting" /></template>
