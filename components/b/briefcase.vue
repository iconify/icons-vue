<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_7iqepwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_7iqepwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:briefcase" /></template>
