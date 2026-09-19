<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzcjqdbir.css';
import '../../css/u/upwfrwbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jzcjqdbir"/><path class="upwfrwbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-notifications-outline" /></template>
