<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/p/p-2b63b8i.css';
import '../../css/q/qnpqtcbjn.css';
import '../../css/j/jxwumcbuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p-2b63b8i"/><path class="qnpqtcbjn"/><path class="jxwumcbuv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:long-sleeve-shirt" /></template>
