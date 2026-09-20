<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li5e-nbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="li5e-nbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-b" /></template>
