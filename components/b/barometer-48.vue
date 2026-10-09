<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hac57wbhi.css';
import '../../css/m/mayk6bclt.css';
import '../../css/g/g5aipabgd.css';
import '../../css/f/f1kd_obxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hac57wbhi"/><path class="mayk6bclt"/><path class="g5aipabgd"/><path class="f1kd_obxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:barometer-48" /></template>
