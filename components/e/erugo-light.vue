<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhbyxpbbq.css';
import '../../css/q/qxnbbh5_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zhbyxpbbq"/><path class="qxnbbh5_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:erugo-light" /></template>
