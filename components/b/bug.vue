<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm-rn_6_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xm-rn_6_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:bug" /></template>
