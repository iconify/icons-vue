<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7f46ac0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7f46ac0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:cloud-loading-bold" /></template>
