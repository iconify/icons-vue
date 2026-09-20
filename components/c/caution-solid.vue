<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eie4bs6wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eie4bs6wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:caution-solid" /></template>
