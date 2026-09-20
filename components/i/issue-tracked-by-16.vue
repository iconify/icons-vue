<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk5hyp-iw.css';
import '../../css/d/dhnqkbc9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mk5hyp-iw"/><path class="dhnqkbc9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:issue-tracked-by-16" /></template>
