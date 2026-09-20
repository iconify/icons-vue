<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmi_cmbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cmi_cmbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:compass" /></template>
