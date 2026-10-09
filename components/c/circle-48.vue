<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hac57wbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hac57wbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:circle-48" /></template>
