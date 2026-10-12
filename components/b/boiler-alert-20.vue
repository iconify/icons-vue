<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jisgs1lqi.css';
import '../../css/u/uktn-1b8e.css';
import '../../css/n/nq5_p_bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jisgs1lqi"/><path class="uktn-1b8e"/><path class="nq5_p_bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:boiler-alert-20" /></template>
