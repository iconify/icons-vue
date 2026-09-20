<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opd2cccpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="opd2cccpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:gradient-2-bold" /></template>
