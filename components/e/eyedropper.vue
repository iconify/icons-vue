<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izh_9ib_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="izh_9ib_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:eyedropper" /></template>
