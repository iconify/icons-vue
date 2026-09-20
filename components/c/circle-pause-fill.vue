<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvdfu_mpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fvdfu_mpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-pause-fill" /></template>
