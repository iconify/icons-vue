<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijvhu-brd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ijvhu-brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:folder-open" /></template>
