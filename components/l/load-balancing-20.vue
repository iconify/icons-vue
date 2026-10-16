<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1osud8tz.css';
import '../../css/s/spvzilqpr.css';
import '../../css/a/aqd5nkwct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j1osud8tz"/><path class="spvzilqpr"/><path class="aqd5nkwct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:load-balancing-20" /></template>
