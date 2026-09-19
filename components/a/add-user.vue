<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz556xbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":680,"height":850};
const content = `<path class="nz556xbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:add-user" /></template>
