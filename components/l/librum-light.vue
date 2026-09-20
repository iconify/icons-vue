<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jro60-bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jro60-bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:librum-light" /></template>
