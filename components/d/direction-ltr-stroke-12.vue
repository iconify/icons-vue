<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aez2ipb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="aez2ipb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:direction-ltr-stroke-12" /></template>
