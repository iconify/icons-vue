<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2b7ppscw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary u2b7ppscw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:lungs-duotone" /></template>
