<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg8-hfdun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="jg8-hfdun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:kaaba" /></template>
