<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y132o_brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y132o_brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-forint" /></template>
