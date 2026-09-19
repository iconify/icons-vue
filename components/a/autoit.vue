<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdy0823vy.css';
import '../../css/e/edp5htv8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wdy0823vy"/><path class="edp5htv8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:autoit" /></template>
