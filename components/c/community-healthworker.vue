<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js7zi3nwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="js7zi3nwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:community-healthworker" /></template>
