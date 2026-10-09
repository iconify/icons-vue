<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnkbx2uas.css';
import '../../css/j/jvdojbb4j.css';
import '../../css/j/j5lb_-btt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bnkbx2uas"/><path class="jvdojbb4j"/><path class="j5lb_-btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:headset-20" /></template>
