<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsibuhbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jsibuhbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:briefcase-with-gas-flame" /></template>
