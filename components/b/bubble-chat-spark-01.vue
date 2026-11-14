<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/om48obbxc.css';
import '../../css/c/ce76g-b8x.css';
import '../../css/e/e60a0hbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="om48obbxc"/><path class="ce76g-b8x"/><path class="e60a0hbxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bubble-chat-spark-01" /></template>
