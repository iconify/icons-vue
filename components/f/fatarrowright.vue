<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fimc63bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="fimc63bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:fatarrowright" /></template>
