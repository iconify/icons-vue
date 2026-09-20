<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulco_5bbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ulco_5bbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:integral-distribute-filled" /></template>
