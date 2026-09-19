<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqe3ykbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rqe3ykbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:high-voltage" /></template>
