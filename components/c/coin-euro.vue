<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpcp248iu.css';
import '../../css/f/frl5hnbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dpcp248iu"/><path class="frl5hnbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:coin-euro" /></template>
