<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2_9i5x-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="o2_9i5x-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:check-circle-fill-12" /></template>
