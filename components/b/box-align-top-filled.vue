<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daaah39dx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="daaah39dx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:box-align-top-filled" /></template>
