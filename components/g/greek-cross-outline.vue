<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5hdy8lkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h5hdy8lkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:greek-cross-outline" /></template>
