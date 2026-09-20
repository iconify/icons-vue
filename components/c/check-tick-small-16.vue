<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3b2z9bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l3b2z9bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:check-tick-small-16" /></template>
