<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhc3qnbeu.css';
import '../../css/z/zv-53k7bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lhc3qnbeu"/><path class="zv-53k7bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-nutrition" /></template>
