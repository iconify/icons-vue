<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6q_o_wdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6q_o_wdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:aas-project-empty" /></template>
