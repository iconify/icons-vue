<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlemfdc9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tlemfdc9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bitbucket" /></template>
