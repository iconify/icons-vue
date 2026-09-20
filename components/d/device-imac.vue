<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2n1_ac4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2n1_ac4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-imac" /></template>
