<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9gsc0brp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="q9gsc0brp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:file-circle-check" /></template>
