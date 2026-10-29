<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-7s1tbdr.css';
import '../../css/d/ds0uwvbso.css';
import '../../css/t/te1bgvv9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-shadow y-7s1tbdr"/><path class="ds0uwvbso wm-k"/><path class="te1bgvv9h wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:chevron-right" /></template>
