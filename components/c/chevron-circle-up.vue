<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgnmve-ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zgnmve-ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:chevron-circle-up" /></template>
