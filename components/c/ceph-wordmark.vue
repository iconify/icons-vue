<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxt2zmbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xxt2zmbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:ceph-wordmark" /></template>
