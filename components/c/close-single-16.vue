<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9m3agbju.css';
import '../../css/z/zc_lys0dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n9m3agbju"/><path clip-rule="evenodd" class="zc_lys0dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:close-single-16" /></template>
