<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm6m-bc7r.css';
import '../../css/k/kwze97erm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="lm6m-bc7r"/><path class="kwze97erm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:diamond-suit" /></template>
