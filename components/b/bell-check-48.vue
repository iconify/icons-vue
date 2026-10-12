<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msmn8bbfm.css';
import '../../css/x/xgyzx9bhy.css';
import '../../css/z/z4sj3ixdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="msmn8bbfm"/><path class="xgyzx9bhy"/><path class="z4sj3ixdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-check-48" /></template>
