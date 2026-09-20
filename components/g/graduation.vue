<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltp2xkbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ltp2xkbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:graduation" /></template>
