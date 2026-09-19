<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7sl2bb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="m7sl2bb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:child-rifle" /></template>
