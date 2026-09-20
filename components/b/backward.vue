<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9lr3pbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e9lr3pbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:backward" /></template>
