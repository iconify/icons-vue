<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og380tjvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="og380tjvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:float-right-solid" /></template>
