<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqamdbc7e.css';
import '../../css/n/nmg5wwk4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":144,"height":144};
const content = `<path class="zqamdbc7e"/><path class="nmg5wwk4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kanboard" /></template>
