<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_42c7mmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_42c7mmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-cloud-lightning" /></template>
