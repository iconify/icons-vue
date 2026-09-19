<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jar0caccs.css';
import '../../css/l/loy56xi0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jar0caccs"/><path class="loy56xi0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-right-01-filled" /></template>
