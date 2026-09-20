<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crk05fz0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crk05fz0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:indent-increase" /></template>
