<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqdezmpfc.css';
import '../../css/d/dqxdjrbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iqdezmpfc"/><path class="dqxdjrbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crimper-20" /></template>
