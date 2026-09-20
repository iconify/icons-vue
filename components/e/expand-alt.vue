<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq0k16bti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nq0k16bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:expand-alt" /></template>
