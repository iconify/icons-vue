<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_vdx0c-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="o_vdx0c-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:letter-o" /></template>
