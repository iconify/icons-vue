<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pako11bqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pako11bqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circles-3-plus" /></template>
