<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn--p_9ji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn--p_9ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:bluetooth-fill" /></template>
