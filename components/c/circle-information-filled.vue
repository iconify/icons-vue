<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye6mt9rky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ye6mt9rky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:circle-information-filled" /></template>
