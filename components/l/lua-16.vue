<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qudowwo1l.css';
import '../../css/r/rvdw2qbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qudowwo1l"/><path class="rvdw2qbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:lua-16" /></template>
