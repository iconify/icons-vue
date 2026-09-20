<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9_od2b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="r9_od2b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:dog-park-11" /></template>
