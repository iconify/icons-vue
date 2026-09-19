<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnhtjtfld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nnhtjtfld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:drawer2" /></template>
