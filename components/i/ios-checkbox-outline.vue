<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9m2_kb3v.css';
import '../../css/d/d9vrg4bmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u9m2_kb3v"/><path class="d9vrg4bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-checkbox-outline" /></template>
