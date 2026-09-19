<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay2oc-bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ay2oc-bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:anchor-circle-exclamation" /></template>
