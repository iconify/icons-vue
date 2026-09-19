<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa19cjbet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="oa19cjbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:batteryaltcharging" /></template>
