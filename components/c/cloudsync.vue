<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohf2_-0nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ohf2_-0nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cloudsync" /></template>
