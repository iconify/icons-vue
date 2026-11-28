<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwp7mzb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwp7mzb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:help-circle" /></template>
