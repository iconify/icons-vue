<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptpl-x96t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ptpl-x96t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:edit-redo-stroke-16" /></template>
