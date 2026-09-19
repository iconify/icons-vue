<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcxadpb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":16};
const content = `<path class="dcxadpb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:keyboard" /></template>
