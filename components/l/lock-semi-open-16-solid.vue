<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgz4_hbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qgz4_hbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:lock-semi-open-16-solid" /></template>
