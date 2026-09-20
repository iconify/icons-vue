<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms_-knb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ms_-knb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:campsite-with-pound" /></template>
