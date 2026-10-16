<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kblqbnvqy.css';
import '../../css/t/timwp37xc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kblqbnvqy"/><path class="timwp37xc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-prismatic-48-bold" /></template>
