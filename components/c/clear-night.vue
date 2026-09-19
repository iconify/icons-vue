<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsy-v4bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xsy-v4bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:clear-night" /></template>
