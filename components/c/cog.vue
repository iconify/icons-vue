<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt0195bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="xt0195bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:cog" /></template>
