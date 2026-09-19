<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5ji-z8yd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k5ji-z8yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:hand-peace" /></template>
