<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt6-z2b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jt6-z2b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:beets-light" /></template>
