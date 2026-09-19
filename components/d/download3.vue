<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhgfm9vyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yhgfm9vyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:download3" /></template>
