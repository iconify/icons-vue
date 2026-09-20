<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv_4-pb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vv_4-pb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:atm" /></template>
