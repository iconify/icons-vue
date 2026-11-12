<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf7_-71-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qf7_-71-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:db-ui-dark" /></template>
