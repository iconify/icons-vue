<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7d7_r7ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v7d7_r7ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:cordova" /></template>
