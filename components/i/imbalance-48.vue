<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycclpjbnb.css';
import '../../css/n/ndahk2b0e.css';
import '../../css/n/nh3pp-bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ycclpjbnb"/><path class="ndahk2b0e"/><path class="nh3pp-bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:imbalance-48" /></template>
