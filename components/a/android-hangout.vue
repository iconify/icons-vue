<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq_3h82mi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lq_3h82mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-hangout" /></template>
