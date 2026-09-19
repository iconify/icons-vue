<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv2zpyesr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":591,"height":677};
const content = `<path class="pv2zpyesr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:checkboxempty" /></template>
