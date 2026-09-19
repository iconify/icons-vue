<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa_p6gi4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="fa_p6gi4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:earth-net-o" /></template>
