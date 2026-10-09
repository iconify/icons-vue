<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk86n9brf.css';
import '../../css/x/xn-ip-jci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bk86n9brf"/><path class="xn-ip-jci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:beer-48" /></template>
