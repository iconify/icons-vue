<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc-py-bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gc-py-bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:bulb" /></template>
