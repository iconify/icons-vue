<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvcpefbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bvcpefbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:leaf-fill-16" /></template>
