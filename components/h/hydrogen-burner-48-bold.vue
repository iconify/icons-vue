<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjhy8yb-f.css';
import '../../css/f/f9b4udbcs.css';
import '../../css/o/o0bd2q3dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tjhy8yb-f"/><path class="f9b4udbcs"/><path class="o0bd2q3dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-burner-48-bold" /></template>
