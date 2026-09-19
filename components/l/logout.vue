<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbpddbcjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1188,"height":1000};
const content = `<path class="xbpddbcjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:logout" /></template>
