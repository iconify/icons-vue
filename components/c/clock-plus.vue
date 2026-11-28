<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmh8u_78t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmh8u_78t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:clock-plus" /></template>
