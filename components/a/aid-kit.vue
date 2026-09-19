<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbc_uw_bh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qbc_uw_bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:aid-kit" /></template>
