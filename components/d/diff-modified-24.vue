<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-yovpx2o.css';
import '../../css/y/ywduolbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-yovpx2o"/><path class="ywduolbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:diff-modified-24" /></template>
