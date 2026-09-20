<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1bbw5cfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":619,"height":88};
const content = `<path class="i1bbw5cfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:five-guys" /></template>
