<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyhjk8bde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iyhjk8bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:briefcase-with-phone-top-right" /></template>
