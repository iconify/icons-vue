<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1sze7i_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y1sze7i_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:bazel" /></template>
