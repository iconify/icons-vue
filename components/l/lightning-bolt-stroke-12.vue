<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulu84p6_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ulu84p6_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:lightning-bolt-stroke-12" /></template>
