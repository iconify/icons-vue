<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r87km9-rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="r87km9-rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:equals-duo" /></template>
