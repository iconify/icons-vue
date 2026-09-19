<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/seqe-2bgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="seqe-2bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-double-down-16-solid" /></template>
