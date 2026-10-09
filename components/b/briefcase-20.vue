<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2_8-nb1y.css';
import '../../css/f/fbgnz0ewn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n2_8-nb1y"/><path class="fbgnz0ewn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:briefcase-20" /></template>
