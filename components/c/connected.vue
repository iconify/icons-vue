<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihk-rkbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="ihk-rkbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:connected" /></template>
