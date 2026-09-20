<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wism3vaym.css';
import '../../css/r/r73utib8z.css';
import '../../css/u/u9hq09b6k.css';
import '../../css/s/s__9l0bok.css';
import '../../css/d/d79nn7b9j.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="wism3vaym"/><path class="r73utib8z"/><path class="u9hq09b6k"/><path class="s__9l0bok"/><path class="d79nn7b9j"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-jordan" /></template>
