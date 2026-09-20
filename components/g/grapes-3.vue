<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb3ujssrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gb3ujssrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:grapes-3" /></template>
