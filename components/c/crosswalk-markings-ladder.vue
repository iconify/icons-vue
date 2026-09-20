<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mibv8f8tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mibv8f8tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:crosswalk-markings-ladder" /></template>
