<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6o6gtbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w6o6gtbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:assistive-listening-systems" /></template>
