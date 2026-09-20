<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9mxw7bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="k9mxw7bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:curve" /></template>
