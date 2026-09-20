<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcfear6ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dcfear6ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:application" /></template>
