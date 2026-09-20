<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh_sqt51j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kh_sqt51j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:caret-vertical-small-outline" /></template>
