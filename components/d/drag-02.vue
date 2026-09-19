<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peggr9bzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="peggr9bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:drag-02" /></template>
