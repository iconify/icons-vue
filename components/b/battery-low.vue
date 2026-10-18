<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf5_e-pql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf5_e-pql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:battery-low" /></template>
