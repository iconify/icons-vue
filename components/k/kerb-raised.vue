<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w59onrtks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w59onrtks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:kerb-raised" /></template>
