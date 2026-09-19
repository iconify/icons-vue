<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to1fjxbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="to1fjxbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:ellipsis" /></template>
