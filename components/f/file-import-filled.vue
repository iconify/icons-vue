<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgkjyd2eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pgkjyd2eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-import-filled" /></template>
