<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v07i1dbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v07i1dbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:keystone" /></template>
