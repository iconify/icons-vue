<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-v_eybct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-v_eybct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:box" /></template>
