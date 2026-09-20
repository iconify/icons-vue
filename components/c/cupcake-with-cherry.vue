<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7rz5mx2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r7rz5mx2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cupcake-with-cherry" /></template>
