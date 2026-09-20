<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k92ore-6n.css';
import '../../css/c/cr42b6bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k92ore-6n"/><path class="cr42b6bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:compose-16" /></template>
