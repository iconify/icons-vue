<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vawghnbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":216,"height":432};
const content = `<path class="vawghnbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:battery-unknown" /></template>
