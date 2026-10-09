<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atysxlblu.css';
import '../../css/g/g3wujfbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="atysxlblu"/><path class="g3wujfbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charging-schedule-48" /></template>
