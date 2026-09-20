<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpu6mrbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpu6mrbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:aerial-lift-filled" /></template>
