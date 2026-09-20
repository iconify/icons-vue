<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7cvghjjq.css';
import '../../css/x/x9yd_cc7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o7cvghjjq"/><path clip-rule="evenodd" class="x9yd_cc7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:id-card-16" /></template>
