<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teneazb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="teneazb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:balance-scale-left" /></template>
