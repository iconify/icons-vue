<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztwu7ut0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ztwu7ut0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:bat" /></template>
