<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oawkc0bme.css';
import '../../css/e/esmev4g_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oawkc0bme"/><path class="esmev4g_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-right-20" /></template>
