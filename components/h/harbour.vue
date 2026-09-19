<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaxktnbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eaxktnbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:harbour" /></template>
