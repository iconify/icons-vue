<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqcf1z8cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eqcf1z8cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:login-3-bold" /></template>
