<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk7a2myob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hk7a2myob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:list-beside-checkmark" /></template>
