<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqosfp8bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dqosfp8bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:crown-16-solid" /></template>
