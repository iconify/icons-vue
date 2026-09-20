<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h38u9um-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h38u9um-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:google-streetview-outline" /></template>
