<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zigi0wfpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zigi0wfpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-moon-48" /></template>
