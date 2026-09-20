<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v61xlebtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v61xlebtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:cain" /></template>
