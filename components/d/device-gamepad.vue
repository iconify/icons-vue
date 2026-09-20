<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/optm_q_ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="optm_q_ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-gamepad" /></template>
