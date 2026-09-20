<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7jlfytys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="j7jlfytys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:archery" /></template>
