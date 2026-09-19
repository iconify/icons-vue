<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fes3r4mpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":455,"height":512};
const content = `<path class="fes3r4mpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:janet" /></template>
