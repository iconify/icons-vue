<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d47xi2b9o.css';
import '../../css/y/yt1sn-2sn.css';
import '../../css/o/oisne4m_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d47xi2b9o"/><path class="yt1sn-2sn"/><path class="oisne4m_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:euro" /></template>
