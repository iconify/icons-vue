<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl91ypb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="nl91ypb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:aerialway-11" /></template>
