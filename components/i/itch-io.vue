<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg2o69bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sg2o69bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:itch-io" /></template>
