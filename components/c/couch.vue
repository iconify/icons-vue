<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpevyce_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zpevyce_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:couch" /></template>
