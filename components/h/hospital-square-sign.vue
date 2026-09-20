<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i03bjx0du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i03bjx0du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:hospital-square-sign" /></template>
