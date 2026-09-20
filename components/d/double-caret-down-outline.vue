<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp_plwb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kp_plwb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:double-caret-down-outline" /></template>
