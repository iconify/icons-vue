<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtcrmjity.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rtcrmjity"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-add-circle" /></template>
