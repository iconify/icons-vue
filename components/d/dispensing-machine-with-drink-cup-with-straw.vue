<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kex-dpb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kex-dpb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dispensing-machine-with-drink-cup-with-straw" /></template>
