<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lr8euubyt.css';
import '../../css/y/ykg6whbsy.css';
import '../../css/r/retufz7fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":88,"height":88};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="lr8euubyt"/><path class="ykg6whbsy"/><path class="retufz7fu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:chart-pie" /></template>
