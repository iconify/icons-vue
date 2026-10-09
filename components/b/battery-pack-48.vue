<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-kp5908v.css';
import '../../css/x/xhbmkr9uj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l-kp5908v"/><path class="xhbmkr9uj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-pack-48" /></template>
