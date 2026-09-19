<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhl-0tduv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="bhl-0tduv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:botl-2" /></template>
