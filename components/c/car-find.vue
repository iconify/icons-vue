<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/errk9qbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="errk9qbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-find" /></template>
