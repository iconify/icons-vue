<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvivg_6-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvivg_6-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:chicken" /></template>
