<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6zlvibhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="q6zlvibhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:camping" /></template>
