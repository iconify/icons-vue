<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf_i5toqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zf_i5toqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:dumbbell" /></template>
