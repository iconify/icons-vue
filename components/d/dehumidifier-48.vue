<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie-wxdblp.css';
import '../../css/j/jv2hyob1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ie-wxdblp"/><path class="jv2hyob1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dehumidifier-48" /></template>
