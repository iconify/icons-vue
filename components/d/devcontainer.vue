<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pen3qlbpt.css';
import '../../css/q/qmyv_61bs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pen3qlbpt"/><path class="qmyv_61bs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:devcontainer" /></template>
