<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0xc77b1s.css';
import '../../css/v/v8t77j0kk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l0xc77b1s"/><path class="v8t77j0kk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:box" /></template>
