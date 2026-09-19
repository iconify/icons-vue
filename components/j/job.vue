<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvvn3n76x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvvn3n76x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:job" /></template>
