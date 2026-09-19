<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugiu9abnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ugiu9abnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:arrow-down-right" /></template>
