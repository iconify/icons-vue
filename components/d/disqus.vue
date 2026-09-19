<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjn9m-sfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":416};
const content = `<path class="rjn9m-sfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:disqus" /></template>
