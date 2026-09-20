<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvcv351wn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pvcv351wn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bicycle-under-taxi-checkerboard" /></template>
