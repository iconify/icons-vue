<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upqsv0b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="upqsv0b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:flag-outline" /></template>
