<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfmy84bkp.css';
import '../../css/r/rgmiyo8xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pfmy84bkp"/><path class="rgmiyo8xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chef-knife-48-bold" /></template>
