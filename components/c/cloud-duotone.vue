<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_u455h9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_u455h9j primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-duotone" /></template>
