<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqu_scb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qqu_scb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:happy2" /></template>
