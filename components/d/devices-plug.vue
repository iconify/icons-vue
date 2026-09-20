<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn6e9-bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kn6e9-bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:devices-plug" /></template>
