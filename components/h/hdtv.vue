<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afl_yub5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":832};
const content = `<path class="afl_yub5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:hdtv" /></template>
