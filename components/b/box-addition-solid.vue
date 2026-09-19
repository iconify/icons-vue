<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-2h97zdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x-2h97zdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:box-addition-solid" /></template>
