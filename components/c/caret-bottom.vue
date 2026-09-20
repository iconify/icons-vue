<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb2m02b9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="eb2m02b9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:caret-bottom" /></template>
