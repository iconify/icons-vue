<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a92d54b2y.css';
import '../../css/h/hubseccej.css';
import '../../css/v/vl5abyl6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a92d54b2y"/><path class="hubseccej"/><path class="vl5abyl6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-up-down-48" /></template>
