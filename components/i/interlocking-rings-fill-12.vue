<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgxf6ebmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xgxf6ebmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:interlocking-rings-fill-12" /></template>
