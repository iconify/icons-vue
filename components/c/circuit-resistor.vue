<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp3_k5mkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kp3_k5mkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circuit-resistor" /></template>
