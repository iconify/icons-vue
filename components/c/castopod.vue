<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzgwzi7wr.css';
import '../../css/s/s7ybahwbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gzgwzi7wr"/><path class="s7ybahwbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:castopod" /></template>
