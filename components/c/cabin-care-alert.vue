<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8_timb4b.css';
import '../../css/n/nqwt54z4d.css';
import '../../css/c/cqy8vydfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c8_timb4b"/><rect class="nqwt54z4d"/><path class="cqy8vydfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cabin-care-alert" /></template>
