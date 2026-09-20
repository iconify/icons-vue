<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxmxt78rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zxmxt78rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grocy" /></template>
