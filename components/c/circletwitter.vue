<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfam4-egf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bfam4-egf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circletwitter" /></template>
