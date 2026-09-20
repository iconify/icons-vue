<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa-hsbc_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa-hsbc_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bugatti" /></template>
