<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwvwksbcx.css';
import '../../css/b/bk5oq1bpa.css';
import '../../css/j/jz6_h2bfq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 qwvwksbcx"/><path class="bk5oq1bpa clr-i-outline clr-i-outline-path-2"/><path class="clr-i-outline clr-i-outline-path-3 jz6_h2bfq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:align-left-line" /></template>
