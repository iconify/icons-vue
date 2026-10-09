<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g41iklb0r.css';
import '../../css/t/tbd4cl6-p.css';
import '../../css/x/xak4i3mwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g41iklb0r"/><path class="tbd4cl6-p"/><path class="xak4i3mwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:blade-recycling-20-bold" /></template>
