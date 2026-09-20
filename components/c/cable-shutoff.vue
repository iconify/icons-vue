<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn-xrwb_q.css';
import '../../css/f/fs5_8vkqb.css';
import '../../css/k/k-njt2b4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dn-xrwb_q"/><path class="fs5_8vkqb"/><path class="k-njt2b4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:cable-shutoff" /></template>
