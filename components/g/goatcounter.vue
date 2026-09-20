<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuv1kqflf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cuv1kqflf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:goatcounter" /></template>
