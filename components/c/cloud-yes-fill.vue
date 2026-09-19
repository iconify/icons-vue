<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_q1tgnww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r_q1tgnww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:cloud-yes-fill" /></template>
