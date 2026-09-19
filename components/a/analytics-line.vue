<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdxbmxx-r.css';
import '../../css/b/buwbwftnq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 tdxbmxx-r"/><path class="buwbwftnq clr-i-outline clr-i-outline-path-2"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:analytics-line" /></template>
