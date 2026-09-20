<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_tqropmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="b_tqropmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:ellipsis" /></template>
