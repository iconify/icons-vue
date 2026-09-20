<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2bqtbcvs.css';
import '../../css/u/uq8jn4bmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a2bqtbcvs"/><path class="uq8jn4bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:android-police" /></template>
