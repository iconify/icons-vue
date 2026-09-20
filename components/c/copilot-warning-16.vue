<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn24bac4r.css';
import '../../css/x/xe3lk6bpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nn24bac4r"/><path class="xe3lk6bpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:copilot-warning-16" /></template>
