<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj72zb1uq.css';
import '../../css/t/tp29nr70i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hj72zb1uq"/><path class="tp29nr70i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:feed-tag-16" /></template>
