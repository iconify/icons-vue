<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avst9pwzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":480};
const content = `<path class="avst9pwzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:dock" /></template>
