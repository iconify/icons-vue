<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqzvsjbqs.css';
import '../../css/p/p1lsw9_1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jqzvsjbqs"/><path class="p1lsw9_1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bludit" /></template>
