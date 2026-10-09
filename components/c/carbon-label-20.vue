<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i49h8ss5i.css';
import '../../css/j/jvv5eu4ka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i49h8ss5i"/><path class="jvv5eu4ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-label-20" /></template>
