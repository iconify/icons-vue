<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx1ebmbsz.css';
import '../../css/c/cic6sccqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kx1ebmbsz"/><path class="cic6sccqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:address-book-remove-16" /></template>
