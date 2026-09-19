<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfivm5bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lfivm5bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:fandango" /></template>
