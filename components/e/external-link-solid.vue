<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muzy7pqmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muzy7pqmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:external-link-solid" /></template>
