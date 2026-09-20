<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upo6hjb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="upo6hjb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lungs-with-right-side-spots" /></template>
